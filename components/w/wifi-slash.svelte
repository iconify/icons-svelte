<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyqpd9b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="cyqpd9b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:wifi-slash" {...props}></Icon>
