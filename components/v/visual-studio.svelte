<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvd_6vbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvd_6vbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:visual-studio" {...props}></Icon>
