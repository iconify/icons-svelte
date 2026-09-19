<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjvphj5er.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjvphj5er"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wall-fuzo" {...props}></Icon>
