<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh87u9zyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mh87u9zyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:spotlight" {...props}></Icon>
