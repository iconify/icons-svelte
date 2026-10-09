<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly6yqgv8r.css';
import '../../css/i/iebf4fbnh.css';
import '../../css/c/cp_vdbbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ly6yqgv8r"/><path class="iebf4fbnh"/><path class="cp_vdbbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermometer-48-bold" {...props}></Icon>
