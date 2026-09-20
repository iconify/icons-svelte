<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fse5akbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fse5akbon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wave-arrow-down" {...props}></Icon>
