<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgjhy3bjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="hgjhy3bjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shopping-catergories-baby-botlle-bottle-milk-family-children-formula-care-child-kid-baby" {...props}></Icon>
