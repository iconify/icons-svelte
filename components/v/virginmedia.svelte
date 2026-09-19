<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfd2wsmwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfd2wsmwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:virginmedia" {...props}></Icon>
