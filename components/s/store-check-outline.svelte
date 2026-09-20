<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsfxc0bui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsfxc0bui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:store-check-outline" {...props}></Icon>
