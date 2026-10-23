<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca2ckcfef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ca2ckcfef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:soap-dispenser-droplet" {...props}></Icon>
