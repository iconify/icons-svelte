<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcny63jha.css';
import '../../css/o/ocydsvu6l.css';
import '../../css/x/xm577jbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bcny63jha"/><path class="ocydsvu6l"/><path class="xm577jbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-panel-bolt-48-bold" {...props}></Icon>
