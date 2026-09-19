<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j779vsc8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j779vsc8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sink" {...props}></Icon>
