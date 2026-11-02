<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me-eke5in.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="me-eke5in"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:xbox-fill" {...props}></Icon>
