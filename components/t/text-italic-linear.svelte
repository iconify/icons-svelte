<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8jiy9bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8jiy9bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-italic-linear" {...props}></Icon>
