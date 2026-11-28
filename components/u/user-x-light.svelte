<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4c8j9fyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="d4c8j9fyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:user-x-light" {...props}></Icon>
