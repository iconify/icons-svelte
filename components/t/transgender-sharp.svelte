<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esy6n4bsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="esy6n4bsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:transgender-sharp" {...props}></Icon>
