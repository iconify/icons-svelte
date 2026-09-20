<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b36ohob0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b36ohob0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:set" {...props}></Icon>
