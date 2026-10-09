<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5f0qtb6n.css';
import '../../css/y/yji6vpglu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w5f0qtb6n"/><path class="yji6vpglu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wheelchair-48-bold" {...props}></Icon>
