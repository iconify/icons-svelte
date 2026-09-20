<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocaw4rbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ocaw4rbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:twitter" {...props}></Icon>
