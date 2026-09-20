<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_hap2nuf.css';
import '../../css/e/ee_cdkb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l_hap2nuf"/><path clip-rule="evenodd" class="ee_cdkb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:run-debug-16" {...props}></Icon>
