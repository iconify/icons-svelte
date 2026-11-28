<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abu8hlbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abu8hlbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:users-minus" {...props}></Icon>
