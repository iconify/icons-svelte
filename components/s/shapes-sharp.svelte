<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6gsu_bib.css';
import '../../css/h/hn50n_brq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i6gsu_bib"/><path class="hn50n_brq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:shapes-sharp" {...props}></Icon>
