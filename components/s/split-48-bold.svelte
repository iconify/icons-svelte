<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l46kpabms.css';
import '../../css/v/vca0g8bfr.css';
import '../../css/q/q9qit9bpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l46kpabms"/><path class="vca0g8bfr"/><path class="q9qit9bpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:split-48-bold" {...props}></Icon>
