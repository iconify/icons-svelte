<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyr-9pbza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fyr-9pbza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:trojan" {...props}></Icon>
