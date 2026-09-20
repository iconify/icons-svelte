<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt924p9ep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pt924p9ep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:router-network-wireless" {...props}></Icon>
