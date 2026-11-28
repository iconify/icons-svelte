<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf39ct00c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sf39ct00c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:stop-solid" {...props}></Icon>
