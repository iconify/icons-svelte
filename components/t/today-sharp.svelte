<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg-uejb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dg-uejb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:today-sharp" {...props}></Icon>
