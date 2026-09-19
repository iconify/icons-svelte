<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmmn3abfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gmmn3abfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:send-sharp" {...props}></Icon>
