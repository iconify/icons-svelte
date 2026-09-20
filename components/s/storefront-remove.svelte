<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw-_4ft-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw-_4ft-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:storefront-remove" {...props}></Icon>
