<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edp4vc3jr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":49.2,"height":49.2,"left":19.5,"top":18.3};
const content = `<path class="edp4vc3jr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:unisoc" {...props}></Icon>
