<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k56d62gzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k56d62gzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:text-bulk-round" {...props}></Icon>
