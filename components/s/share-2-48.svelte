<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5jpf8r7p.css';
import '../../css/c/ctxjx93qy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t5jpf8r7p"/><path class="ctxjx93qy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:share-2-48" {...props}></Icon>
