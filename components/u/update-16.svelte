<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-lm3x_hr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a-lm3x_hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:update-16" {...props}></Icon>
