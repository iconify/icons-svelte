<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pedr4_bjp.css';
import '../../css/w/wk04f5vlf.css';
import '../../css/o/o6pwbnxip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pedr4_bjp"/><path class="wk04f5vlf"/><path class="o6pwbnxip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:synchronous-condenser-48-bold" {...props}></Icon>
