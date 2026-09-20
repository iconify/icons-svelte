<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h13hmac8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="h13hmac8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:shuffle" {...props}></Icon>
