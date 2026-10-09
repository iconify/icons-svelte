<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le28xpbbv.css';
import '../../css/o/o8rtphxyj.css';
import '../../css/c/czocnxqcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="le28xpbbv"/><path class="o8rtphxyj"/><path class="czocnxqcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:satellite-48" {...props}></Icon>
