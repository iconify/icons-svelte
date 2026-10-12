<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoihmqbaa.css';
import '../../css/l/lx3ia5bzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aoihmqbaa"/><path class="lx3ia5bzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:shopping-cart-stroke-20" {...props}></Icon>
