<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqtragb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":24};
const content = `<path class="mqtragb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:troy" {...props}></Icon>
