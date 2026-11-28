<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irw_shbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irw_shbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:search-activity-solid" {...props}></Icon>
