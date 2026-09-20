<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awydey58c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awydey58c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:scanner" {...props}></Icon>
