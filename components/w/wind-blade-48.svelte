<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hftzc6bjl.css';
import '../../css/g/gwf5562uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hftzc6bjl"/><path class="gwf5562uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-blade-48" {...props}></Icon>
