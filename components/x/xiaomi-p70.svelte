<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih6dy_bma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ih6dy_bma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:xiaomi-p70" {...props}></Icon>
