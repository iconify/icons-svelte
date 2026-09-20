<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkr1c6dyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lkr1c6dyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:signal-strength-0" {...props}></Icon>
