<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu9h76b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qu9h76b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:window-maximize" {...props}></Icon>
