<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bboy_xreu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bboy_xreu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shark" {...props}></Icon>
