<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6ubawbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r6ubawbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:usb-drive-fill" {...props}></Icon>
