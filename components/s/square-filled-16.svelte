<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j19d5_lcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j19d5_lcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:square-filled-16" {...props}></Icon>
