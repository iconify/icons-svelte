<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1ovthbog.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tre2nwb3v.css';
import '../../css/m/mx-0x3bae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1ovthbog secondary"/><g class="dt0cm9dhy primary"><path class="tre2nwb3v"/><path class="mx-0x3bae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sunflower-duo" {...props}></Icon>
