<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq85p23jt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qq85p23jt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:wifi-none-solid" {...props}></Icon>
