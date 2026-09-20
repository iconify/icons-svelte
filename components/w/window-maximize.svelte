<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2zrydb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2zrydb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:window-maximize" {...props}></Icon>
