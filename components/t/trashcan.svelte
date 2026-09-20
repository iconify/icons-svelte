<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi1r8vbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="vi1r8vbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:trashcan" {...props}></Icon>
