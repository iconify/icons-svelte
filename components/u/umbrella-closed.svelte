<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s46vpd6ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s46vpd6ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:umbrella-closed" {...props}></Icon>
