<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnwn6gu-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnwn6gu-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:valve-open" {...props}></Icon>
