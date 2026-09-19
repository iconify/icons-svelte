<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8f30sbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s8f30sbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:tablet" {...props}></Icon>
