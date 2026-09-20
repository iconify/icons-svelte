<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwtan5y3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwtan5y3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tor" {...props}></Icon>
