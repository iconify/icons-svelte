<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy84kabif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zy84kabif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:tablets" {...props}></Icon>
