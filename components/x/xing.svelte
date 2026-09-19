<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8jj7g7sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="m8jj7g7sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:xing" {...props}></Icon>
