<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_g2p56iu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c_g2p56iu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:triangle-15" {...props}></Icon>
