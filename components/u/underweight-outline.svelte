<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i832tbe8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="i832tbe8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:underweight-outline" {...props}></Icon>
