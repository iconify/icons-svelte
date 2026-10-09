<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngsvkrhta.css';
import '../../css/d/dscex6b8j.css';
import '../../css/s/sb5-4ppir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ngsvkrhta"/><path class="dscex6b8j"/><path class="sb5-4ppir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scaffolding-48-bold" {...props}></Icon>
