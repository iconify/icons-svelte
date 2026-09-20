<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smf9jihll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smf9jihll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:signal-cellular-1" {...props}></Icon>
