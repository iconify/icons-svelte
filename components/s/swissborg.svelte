<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2hovyb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m2hovyb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:swissborg" {...props}></Icon>
