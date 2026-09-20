<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjvpnbfge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjvpnbfge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:script" {...props}></Icon>
