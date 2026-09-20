<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5hk3yb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="g5hk3yb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:tower-broadcast-1" {...props}></Icon>
