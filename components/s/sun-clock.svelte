<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-g7uu0ua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-g7uu0ua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sun-clock" {...props}></Icon>
