<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhe7dvyvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vhe7dvyvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:white-right-backhand-index" {...props}></Icon>
