<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv0sseb2v.css';
import '../../css/h/hgwopu5qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iv0sseb2v"/><path class="hgwopu5qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:sim-card-chip" {...props}></Icon>
