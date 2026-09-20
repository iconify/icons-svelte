<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov-sdpvoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ov-sdpvoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:share-link-remix" {...props}></Icon>
