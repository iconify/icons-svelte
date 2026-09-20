<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv2hi7bej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jv2hi7bej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:tradingview" {...props}></Icon>
