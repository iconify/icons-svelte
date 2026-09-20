<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa6mtc6if.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="aa6mtc6if"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:shapes" {...props}></Icon>
