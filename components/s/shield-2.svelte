<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll5w1cbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ll5w1cbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shield-2" {...props}></Icon>
