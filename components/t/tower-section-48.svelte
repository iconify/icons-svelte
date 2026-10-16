<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnwg1wboc.css';
import '../../css/f/fu_1idbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qnwg1wboc"/><path class="fu_1idbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tower-section-48" {...props}></Icon>
