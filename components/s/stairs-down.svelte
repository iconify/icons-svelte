<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cydns6brp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cydns6brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stairs-down" {...props}></Icon>
