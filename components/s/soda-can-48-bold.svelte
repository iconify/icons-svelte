<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj2y_bb9h.css';
import '../../css/u/u01yqubev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tj2y_bb9h"/><path class="u01yqubev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:soda-can-48-bold" {...props}></Icon>
