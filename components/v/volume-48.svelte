<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9bzs8odx.css';
import '../../css/i/ijrn25w1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r9bzs8odx"/><path class="ijrn25w1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:volume-48" {...props}></Icon>
