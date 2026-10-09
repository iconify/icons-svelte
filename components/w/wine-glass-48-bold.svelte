<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mutfufb4a.css';
import '../../css/e/eo5ryvbqs.css';
import '../../css/t/tjrjm1bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mutfufb4a"/><path class="eo5ryvbqs"/><path class="tjrjm1bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wine-glass-48-bold" {...props}></Icon>
