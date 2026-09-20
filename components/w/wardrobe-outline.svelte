<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h61y9uz1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h61y9uz1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wardrobe-outline" {...props}></Icon>
