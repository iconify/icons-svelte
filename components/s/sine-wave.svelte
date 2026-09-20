<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geswdnj1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="geswdnj1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sine-wave" {...props}></Icon>
