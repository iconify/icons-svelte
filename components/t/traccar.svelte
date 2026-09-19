<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk0w-6brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rk0w-6brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:traccar" {...props}></Icon>
