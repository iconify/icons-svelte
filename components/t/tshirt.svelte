<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqdx4ebjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqdx4ebjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:tshirt" {...props}></Icon>
