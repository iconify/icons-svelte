<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj--35xot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sj--35xot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:skull-with-x-oblique" {...props}></Icon>
