<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk2xr949v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk2xr949v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tumble-dryer-off" {...props}></Icon>
