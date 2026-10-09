<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-pfn5jar.css';
import '../../css/a/anc-0tb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u-pfn5jar"/><path class="anc-0tb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:zoom-out-48-bold" {...props}></Icon>
