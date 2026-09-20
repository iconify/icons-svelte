<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji3_crqts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ji3_crqts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:workbrew-light" {...props}></Icon>
