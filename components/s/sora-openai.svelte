<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u11sn2bte.css';
import '../../css/b/b1hrujb-k.css';
import '../../css/r/rjyxz_brk.css';
import '../../css/f/fk6wuudwj.css';
import '../../css/h/hfj0unbqw.css';
import '../../css/r/rhgj955de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="u11sn2bte"><path class="b1hrujb-k"/><path clip-rule="evenodd" class="rjyxz_brk"/><path class="fk6wuudwj"/><path clip-rule="evenodd" class="hfj0unbqw"/><path clip-rule="evenodd" class="rhgj955de"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sora-openai" {...props}></Icon>
