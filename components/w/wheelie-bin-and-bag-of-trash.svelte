<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwzg04bbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pwzg04bbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wheelie-bin-and-bag-of-trash" {...props}></Icon>
