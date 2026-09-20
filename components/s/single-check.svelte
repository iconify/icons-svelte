<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6ulnw8uw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p6ulnw8uw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:single-check" {...props}></Icon>
