<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hp0ef7eag.css';
import '../../css/b/bb_1k1bwk.css';
import '../../css/b/blzg_nqww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="hp0ef7eag"/><path clip-rule="evenodd" class="bb_1k1bwk"/><path class="blzg_nqww"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:secured" {...props}></Icon>
