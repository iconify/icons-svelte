<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpze4wb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="fpze4wb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:torah" {...props}></Icon>
