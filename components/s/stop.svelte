<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lknh6wbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lknh6wbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stop" {...props}></Icon>
