<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzc1br60k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzc1br60k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:signe" {...props}></Icon>
