<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8xv4ht1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p8xv4ht1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:star-badge-solid" {...props}></Icon>
