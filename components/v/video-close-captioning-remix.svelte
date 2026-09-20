<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3gdu6bme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n3gdu6bme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:video-close-captioning-remix" {...props}></Icon>
