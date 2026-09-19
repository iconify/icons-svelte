<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9cb8g7fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n9cb8g7fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:txt" {...props}></Icon>
