<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8tcwf7xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8tcwf7xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:search-2-ai-fill" {...props}></Icon>
