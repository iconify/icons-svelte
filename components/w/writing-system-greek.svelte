<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpfqdcc8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpfqdcc8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:writing-system-greek" {...props}></Icon>
