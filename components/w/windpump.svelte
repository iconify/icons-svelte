<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7l1neb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j7l1neb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:windpump" {...props}></Icon>
