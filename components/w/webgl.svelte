<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs314zbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs314zbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:webgl" {...props}></Icon>
