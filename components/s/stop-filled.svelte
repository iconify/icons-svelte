<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mibn7eb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="mibn7eb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:stop-filled" {...props}></Icon>
