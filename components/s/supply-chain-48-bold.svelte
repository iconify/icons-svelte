<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9t92f57g.css';
import '../../css/c/c81pk53il.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l9t92f57g"/><path class="c81pk53il"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:supply-chain-48-bold" {...props}></Icon>
