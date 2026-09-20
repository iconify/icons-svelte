<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x53syboks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x53syboks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:trustedshops" {...props}></Icon>
