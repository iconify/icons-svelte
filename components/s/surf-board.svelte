<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbpzzzu3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="zbpzzzu3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:surf-board" {...props}></Icon>
