<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8tbbbvzb.css';
import '../../css/v/vanfr9l2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q8tbbbvzb"/><path class="vanfr9l2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:watch-20-bold" {...props}></Icon>
