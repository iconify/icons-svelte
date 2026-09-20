<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d54k03b9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d54k03b9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:translate-off" {...props}></Icon>
