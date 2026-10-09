<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlkz-3bot.css';
import '../../css/n/n827cbx-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nlkz-3bot"/><path class="n827cbx-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ticket-48" {...props}></Icon>
