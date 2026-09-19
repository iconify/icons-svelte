<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zadz1fz-o.css';
import '../../css/o/oghs20fic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zadz1fz-o"/><path class="oghs20fic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:umbrella-sharp" {...props}></Icon>
