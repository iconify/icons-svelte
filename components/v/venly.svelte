<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_vfp0bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_vfp0bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:venly" {...props}></Icon>
