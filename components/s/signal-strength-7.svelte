<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi1s_1bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vi1s_1bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:signal-strength-7" {...props}></Icon>
