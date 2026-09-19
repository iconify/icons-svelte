<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-llofvpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l-llofvpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wrap-right-fill-16" {...props}></Icon>
