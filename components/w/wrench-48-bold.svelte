<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9a0osi5b.css';
import '../../css/s/s5jqyc38e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x9a0osi5b"/><path class="s5jqyc38e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wrench-48-bold" {...props}></Icon>
