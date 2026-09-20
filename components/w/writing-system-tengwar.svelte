<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3rlgtdqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3rlgtdqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:writing-system-tengwar" {...props}></Icon>
