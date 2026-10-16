<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyir5yn6t.css';
import '../../css/j/jtw39nbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lyir5yn6t"/><path class="jtw39nbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:water-butt-48-bold" {...props}></Icon>
