<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwxmmelya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lwxmmelya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:sync-circle-sharp" {...props}></Icon>
