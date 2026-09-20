<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izo3etbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izo3etbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:vs-code" {...props}></Icon>
