<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_3b78b5d.css';
import '../../css/w/w80p7wbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l_3b78b5d"/><path class="w80p7wbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sticky-note-48" {...props}></Icon>
