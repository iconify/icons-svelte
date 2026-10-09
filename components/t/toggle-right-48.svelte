<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8z5zjbsy.css';
import '../../css/r/rurafzzht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k8z5zjbsy"/><path class="rurafzzht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:toggle-right-48" {...props}></Icon>
