<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1crdphdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e1crdphdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:trail-sign-sharp" {...props}></Icon>
