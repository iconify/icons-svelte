<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt4poo8_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mt4poo8_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:view-grid" {...props}></Icon>
