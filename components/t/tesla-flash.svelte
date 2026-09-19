<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghm6t940e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghm6t940e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tesla-flash" {...props}></Icon>
