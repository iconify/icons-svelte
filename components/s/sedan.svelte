<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dus-44yqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dus-44yqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sedan" {...props}></Icon>
