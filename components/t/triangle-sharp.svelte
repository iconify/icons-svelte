<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2797tbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c2797tbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:triangle-sharp" {...props}></Icon>
