<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4t77hbzd.css';
import '../../css/d/djucoz9_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e4t77hbzd"/><path class="djucoz9_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:warming-stripes-48-bold" {...props}></Icon>
