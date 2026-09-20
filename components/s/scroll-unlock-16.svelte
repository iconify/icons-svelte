<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3wopibcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v3wopibcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:scroll-unlock-16" {...props}></Icon>
