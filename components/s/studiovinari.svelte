<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fted46bav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fted46bav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:studiovinari" {...props}></Icon>
