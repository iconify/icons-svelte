<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dok1_95jx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dok1_95jx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:text-sharp" {...props}></Icon>
