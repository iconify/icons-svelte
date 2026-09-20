<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo_ii94vh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zo_ii94vh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:user-check-solid" {...props}></Icon>
