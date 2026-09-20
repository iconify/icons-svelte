<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktgkes3tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":622,"height":622};
const content = `<path class="ktgkes3tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:uptime-kuma-dark" {...props}></Icon>
