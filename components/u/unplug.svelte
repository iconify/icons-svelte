<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8lwz908c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8lwz908c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:unplug" {...props}></Icon>
