<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlo-1-b1r.css';
import '../../css/h/hgxu9lb6k.css';
import '../../css/r/rt3rcig7i.css';
import '../../css/w/wi0dpbc4a.css';
import '../../css/i/ikpbwe38b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tlo-1-b1r"/><path class="hgxu9lb6k"/><path class="rt3rcig7i"/><path class="wi0dpbc4a"/><path class="ikpbwe38b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-tracker-alert-48" {...props}></Icon>
