<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uexuiinxx.css';
import '../../css/v/vi7of3bpv.css';
import '../../css/g/guzqa6bjs.css';
import '../../css/g/g7lf7dbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="uexuiinxx"/><path class="vi7of3bpv"/><path class="guzqa6bjs"/><path class="g7lf7dbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:shopping-bags" {...props}></Icon>
