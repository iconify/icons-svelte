<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duv2dac2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duv2dac2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:sencha" {...props}></Icon>
