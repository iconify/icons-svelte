<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5qt0b1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ft5qt0b1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:windows-minimize-16" {...props}></Icon>
