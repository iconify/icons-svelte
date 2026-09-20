<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq-kp1o7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="eq-kp1o7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:slash-backward" {...props}></Icon>
