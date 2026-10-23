<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byk9-sb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="byk9-sb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:sheet" {...props}></Icon>
