<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rej6b4bhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rej6b4bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:triangle-filled-16" {...props}></Icon>
