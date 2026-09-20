<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw8y_lyiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zw8y_lyiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:steel-square-and-drafting-compass" {...props}></Icon>
