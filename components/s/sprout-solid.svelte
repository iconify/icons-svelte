<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr59oye-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr59oye-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:sprout-solid" {...props}></Icon>
