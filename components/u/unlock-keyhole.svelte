<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnb3zojbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="bnb3zojbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:unlock-keyhole" {...props}></Icon>
