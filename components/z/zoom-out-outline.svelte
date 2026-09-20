<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys0g26bqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ys0g26bqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:zoom-out-outline" {...props}></Icon>
