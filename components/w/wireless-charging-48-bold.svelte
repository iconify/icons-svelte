<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibs8b-b6s.css';
import '../../css/r/rh7lscyqa.css';
import '../../css/y/y6m516bwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ibs8b-b6s"/><path class="rh7lscyqa"/><path class="y6m516bwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wireless-charging-48-bold" {...props}></Icon>
