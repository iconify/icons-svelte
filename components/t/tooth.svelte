<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6pyiyb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h6pyiyb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:tooth" {...props}></Icon>
