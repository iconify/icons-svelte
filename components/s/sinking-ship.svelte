<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyiztpbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wyiztpbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:sinking-ship" {...props}></Icon>
