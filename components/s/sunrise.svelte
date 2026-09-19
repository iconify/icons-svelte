<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta3fb838w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ta3fb838w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sunrise" {...props}></Icon>
