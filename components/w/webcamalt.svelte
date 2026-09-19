<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc4cqtmyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":833,"height":1024};
const content = `<path class="lc4cqtmyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:webcamalt" {...props}></Icon>
