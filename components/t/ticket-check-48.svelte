<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlkz-3bot.css';
import '../../css/g/gx580lbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nlkz-3bot"/><path class="gx580lbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ticket-check-48" {...props}></Icon>
