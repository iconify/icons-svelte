<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czouxmpzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="czouxmpzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:unicode" {...props}></Icon>
