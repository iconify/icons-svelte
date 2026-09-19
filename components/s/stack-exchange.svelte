<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1yw4pb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="t1yw4pb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:stack-exchange" {...props}></Icon>
