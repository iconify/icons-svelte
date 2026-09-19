<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3g99mb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g3g99mb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:sunny-sharp" {...props}></Icon>
