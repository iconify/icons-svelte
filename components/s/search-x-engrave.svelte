<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/g0ovr4xyu.css';
import '../../css/j/jv-5mvs8v.css';
import '../../css/f/ff6q2eboe.css';
import '../../css/o/olgj5xbvl.css';
import '../../css/h/haqznqbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="g0ovr4xyu wm-k"/><path class="jv-5mvs8v wm-a"/><path class="ff6q2eboe wm-shadow"/><path class="olgj5xbvl wm-k"/><path class="haqznqbfc wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:search-x-engrave" {...props}></Icon>
