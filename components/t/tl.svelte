<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jgv76kwto.css';
import '../../css/a/aspkqopjm.css';
import '../../css/i/ic329ryoo.css';
import '../../css/b/b_rwou1ju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jgv76kwto"/><path clip-rule="evenodd" class="aspkqopjm"/><path clip-rule="evenodd" class="ic329ryoo"/><path clip-rule="evenodd" class="b_rwou1ju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:tl" {...props}></Icon>
