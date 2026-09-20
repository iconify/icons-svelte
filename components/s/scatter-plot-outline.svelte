<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka6dq8sfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ka6dq8sfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:scatter-plot-outline" {...props}></Icon>
