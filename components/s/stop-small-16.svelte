<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5i5oac3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l5i5oac3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:stop-small-16" {...props}></Icon>
