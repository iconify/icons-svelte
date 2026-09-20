<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndq79cc0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndq79cc0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-week-outline" {...props}></Icon>
