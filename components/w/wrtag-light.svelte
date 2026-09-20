<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzna_0bmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mzna_0bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wrtag-light" {...props}></Icon>
