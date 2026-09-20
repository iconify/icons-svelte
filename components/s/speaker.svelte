<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2vz43btc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2vz43btc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:speaker" {...props}></Icon>
