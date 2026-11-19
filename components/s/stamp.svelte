<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w849-nyff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w849-nyff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:stamp" {...props}></Icon>
