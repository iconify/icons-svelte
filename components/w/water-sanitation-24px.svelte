<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws5a_qbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ws5a_qbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:water-sanitation-24px" {...props}></Icon>
