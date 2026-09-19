<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1r3f5ojh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b1r3f5ojh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:shopping-cart" {...props}></Icon>
