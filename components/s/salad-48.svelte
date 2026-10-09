<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1h7svbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o1h7svbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:salad-48" {...props}></Icon>
