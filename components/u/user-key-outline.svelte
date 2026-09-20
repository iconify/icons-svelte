<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9b-n7y7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9b-n7y7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:user-key-outline" {...props}></Icon>
