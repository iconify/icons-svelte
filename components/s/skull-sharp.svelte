<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsh4tibvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wsh4tibvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:skull-sharp" {...props}></Icon>
