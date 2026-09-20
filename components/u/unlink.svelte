<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9-e7g7ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="l9-e7g7ml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:unlink" {...props}></Icon>
