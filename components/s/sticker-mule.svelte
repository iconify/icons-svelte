<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h08u19bjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h08u19bjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sticker-mule" {...props}></Icon>
