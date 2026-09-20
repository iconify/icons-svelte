<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f38ss-bbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f38ss-bbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:web-minus" {...props}></Icon>
