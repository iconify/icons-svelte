<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmtr6bb9i.css';
import '../../css/c/cxqwkvj3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wmtr6bb9i"/><path class="cxqwkvj3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sparkline-48-bold" {...props}></Icon>
