<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01eto0we.css';
import '../../css/w/wlja3wbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h01eto0we"/><path class="wlja3wbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:square-check-48" {...props}></Icon>
