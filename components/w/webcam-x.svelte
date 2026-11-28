<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj2v5si_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pj2v5si_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:webcam-x" {...props}></Icon>
