<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqep3ob2t.css';
import '../../css/p/p9q9isb-a.css';
import '../../css/r/rk00lts6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fqep3ob2t"/><path class="p9q9isb-a"/><path class="rk00lts6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-direction-48-bold" {...props}></Icon>
