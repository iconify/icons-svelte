<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scjxik53c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="scjxik53c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:x-diamond" {...props}></Icon>
