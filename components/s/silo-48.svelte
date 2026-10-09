<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twx0_4--t.css';
import '../../css/s/s9uy0jb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="twx0_4--t"/><path class="s9uy0jb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:silo-48" {...props}></Icon>
