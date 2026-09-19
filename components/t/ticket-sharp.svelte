<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_5uwvqjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h_5uwvqjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:ticket-sharp" {...props}></Icon>
