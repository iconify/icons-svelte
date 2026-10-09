<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfx3nk7mg.css';
import '../../css/d/d5jwctbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wfx3nk7mg"/><path class="d5jwctbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:weir-48" {...props}></Icon>
