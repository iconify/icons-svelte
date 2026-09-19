<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0zqk9bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v0zqk9bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:strikethrough" {...props}></Icon>
