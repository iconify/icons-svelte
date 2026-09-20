<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0t6jfbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h0t6jfbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:webcam-remix" {...props}></Icon>
