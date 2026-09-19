<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nupt5ccee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nupt5ccee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:toilet" {...props}></Icon>
