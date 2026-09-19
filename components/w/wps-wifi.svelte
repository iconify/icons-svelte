<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-s-q8bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-s-q8bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wps-wifi" {...props}></Icon>
