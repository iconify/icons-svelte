<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh2vkhb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oh2vkhb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:wine" {...props}></Icon>
