<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd1f1ab4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kd1f1ab4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:snowflake-and-icicles" {...props}></Icon>
