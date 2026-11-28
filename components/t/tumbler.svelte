<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/aink3vbmj.css';
import '../../css/o/osn-tobkz.css';
import '../../css/f/fsmuwe8bo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="aink3vbmj"/><path class="osn-tobkz"/><path class="fsmuwe8bo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tumbler" {...props}></Icon>
