<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opgu7lbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opgu7lbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:swim" {...props}></Icon>
