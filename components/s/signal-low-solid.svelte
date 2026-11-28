<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wysknn0pv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wysknn0pv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:signal-low-solid" {...props}></Icon>
