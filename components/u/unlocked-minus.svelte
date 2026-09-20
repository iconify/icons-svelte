<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq76meb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uq76meb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:unlocked-minus" {...props}></Icon>
