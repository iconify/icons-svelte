<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozp9g2b1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ozp9g2b1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:server-solid" {...props}></Icon>
