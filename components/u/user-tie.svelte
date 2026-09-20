<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni_0eabwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ni_0eabwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:user-tie" {...props}></Icon>
