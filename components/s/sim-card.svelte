<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od2b1-boe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="od2b1-boe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:sim-card" {...props}></Icon>
