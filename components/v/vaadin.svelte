<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywvj5dbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ywvj5dbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:vaadin" {...props}></Icon>
