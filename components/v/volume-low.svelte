<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs8_ejdrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xs8_ejdrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:volume-low" {...props}></Icon>
