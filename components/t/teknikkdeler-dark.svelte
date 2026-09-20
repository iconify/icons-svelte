<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egzsl3b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="egzsl3b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:teknikkdeler-dark" {...props}></Icon>
