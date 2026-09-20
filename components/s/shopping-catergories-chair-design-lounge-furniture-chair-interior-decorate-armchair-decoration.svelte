<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoa_vzbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="uoa_vzbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shopping-catergories-chair-design-lounge-furniture-chair-interior-decorate-armchair-decoration" {...props}></Icon>
