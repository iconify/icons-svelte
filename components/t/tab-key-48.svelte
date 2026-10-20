<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5ttvzsqn.css';
import '../../css/c/cnq1mrb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t5ttvzsqn"/><path class="cnq1mrb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tab-key-48" {...props}></Icon>
