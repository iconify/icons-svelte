<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gse48h3rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gse48h3rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:speedtest" {...props}></Icon>
