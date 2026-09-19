<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up3p33-bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="up3p33-bz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:shopping-cart" {...props}></Icon>
