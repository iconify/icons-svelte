<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qotdusbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qotdusbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sort-clock-descending-outline" {...props}></Icon>
