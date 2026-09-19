<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvj7bnbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vvj7bnbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:wireguard" {...props}></Icon>
