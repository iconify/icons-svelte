<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss-p3acfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ss-p3acfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:symbol-array" {...props}></Icon>
