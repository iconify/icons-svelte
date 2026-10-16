<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kws3gabmt.css';
import '../../css/h/hjb9uvnoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kws3gabmt"/><path class="hjb9uvnoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:waypoints-48" {...props}></Icon>
