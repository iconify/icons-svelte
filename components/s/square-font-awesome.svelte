<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3jh0x0el.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="t3jh0x0el"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:square-font-awesome" {...props}></Icon>
