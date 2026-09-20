<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdftnwb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdftnwb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:store-settings-outline" {...props}></Icon>
