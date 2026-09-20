<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtkbd7gbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtkbd7gbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:star-moving-fill" {...props}></Icon>
