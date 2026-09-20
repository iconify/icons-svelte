<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ked47iboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ked47iboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:t-bar-lift" {...props}></Icon>
