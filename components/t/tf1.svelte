<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8j7ctm1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8j7ctm1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tf1" {...props}></Icon>
