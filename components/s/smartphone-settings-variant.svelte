<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vefdffbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vefdffbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:smartphone-settings-variant" {...props}></Icon>
