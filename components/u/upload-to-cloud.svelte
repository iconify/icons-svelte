<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp89m8b4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="jp89m8b4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:upload-to-cloud" {...props}></Icon>
