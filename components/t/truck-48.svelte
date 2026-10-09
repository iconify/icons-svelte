<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xujk5fdpi.css';
import '../../css/w/wg4scnbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xujk5fdpi"/><path class="wg4scnbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:truck-48" {...props}></Icon>
