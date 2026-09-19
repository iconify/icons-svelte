<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3nkh24xn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="h3nkh24xn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-zerply" {...props}></Icon>
