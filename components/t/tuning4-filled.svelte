<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxgt88b3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxgt88b3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tuning4-filled" {...props}></Icon>
