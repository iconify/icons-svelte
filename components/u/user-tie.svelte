<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbcyqz5cm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="sbcyqz5cm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:user-tie" {...props}></Icon>
