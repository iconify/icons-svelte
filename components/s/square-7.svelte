<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsf8_ubdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsf8_ubdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:square-7" {...props}></Icon>
