<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rveap4b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rveap4b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:wind-energy" {...props}></Icon>
