<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2s-qrx1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2s-qrx1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:timer-close" {...props}></Icon>
