<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2w5z4str.css';
import '../../css/b/bcmzn-obx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2w5z4str"/><path class="bcmzn-obx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rugby-ball" {...props}></Icon>
