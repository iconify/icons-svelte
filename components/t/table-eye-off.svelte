<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w41a_vb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w41a_vb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-eye-off" {...props}></Icon>
