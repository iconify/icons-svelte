<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgid5pwjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vgid5pwjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:shopping-shipping-upload-information" {...props}></Icon>
