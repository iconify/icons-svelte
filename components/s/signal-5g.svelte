<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq8e39gll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hq8e39gll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:signal-5g" {...props}></Icon>
