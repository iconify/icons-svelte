<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swrm6uh7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="swrm6uh7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:scissors-open" {...props}></Icon>
