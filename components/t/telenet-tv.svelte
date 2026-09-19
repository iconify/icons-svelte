<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgqgi3exg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgqgi3exg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:telenet-tv" {...props}></Icon>
