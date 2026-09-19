<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s46z6zm0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s46z6zm0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:water-bottle-solid" {...props}></Icon>
