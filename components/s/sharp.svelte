<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0zhpp2bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0zhpp2bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sharp" {...props}></Icon>
