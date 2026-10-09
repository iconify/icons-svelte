<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmkkkwifn.css';
import '../../css/e/ea_1x7xoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jmkkkwifn"/><path class="ea_1x7xoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:welding-mask-48" {...props}></Icon>
