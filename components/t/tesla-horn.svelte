<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncb6-0bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncb6-0bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tesla-horn" {...props}></Icon>
