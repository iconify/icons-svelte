<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/goj2twb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="goj2twb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-chevron-left-fill-round" {...props}></Icon>
