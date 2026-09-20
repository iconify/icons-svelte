<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um3c7fi5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um3c7fi5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:store-24-hour" {...props}></Icon>
