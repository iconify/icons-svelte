<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb6xjt88u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rb6xjt88u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:service-outline" {...props}></Icon>
