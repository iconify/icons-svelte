<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptkb62c8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ptkb62c8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:snow-globe-solid" {...props}></Icon>
