<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rul5h6brj.css';
import '../../css/h/hwjgqrbah.css';
import '../../css/o/oqrsy3bng.css';
import '../../css/u/uq11f0fet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rul5h6brj"/><path class="hwjgqrbah"/><path class="oqrsy3bng"/><path class="uq11f0fet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-x-48-bold" {...props}></Icon>
