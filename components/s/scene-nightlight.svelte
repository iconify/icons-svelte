<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gee_04tds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gee_04tds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:scene-nightlight" {...props}></Icon>
