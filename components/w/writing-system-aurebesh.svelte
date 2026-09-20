<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca_tmx52z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ca_tmx52z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:writing-system-aurebesh" {...props}></Icon>
