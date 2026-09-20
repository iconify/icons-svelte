<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lekd1dbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lekd1dbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tick-network-outline" {...props}></Icon>
