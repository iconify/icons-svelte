<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmpeqjlep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmpeqjlep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-row-remove" {...props}></Icon>
