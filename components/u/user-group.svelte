<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3emh-b-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3emh-b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:user-group" {...props}></Icon>
