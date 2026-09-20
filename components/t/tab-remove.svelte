<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w55_-xb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w55_-xb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tab-remove" {...props}></Icon>
