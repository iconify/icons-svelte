<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agcsd6j3i.css';
import '../../css/r/rps7bbcge.css';
import '../../css/n/nrn2j2qgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="agcsd6j3i"/><path class="rps7bbcge"/><path class="nrn2j2qgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shrink-48" {...props}></Icon>
