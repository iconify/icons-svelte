<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlw-j7bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlw-j7bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:summation" {...props}></Icon>
