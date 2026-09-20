<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avrte1b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="avrte1b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:semaphore-light" {...props}></Icon>
