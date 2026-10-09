<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w30mb-bsx.css';
import '../../css/x/xoi6f6nox.css';
import '../../css/p/poe4r5-le.css';
import '../../css/e/ekwadbbdy.css';
import '../../css/l/luqa3jbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w30mb-bsx"/><path class="xoi6f6nox"/><path class="poe4r5-le"/><path class="ekwadbbdy"/><path class="luqa3jbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-turbine-offshore-spinning-48" {...props}></Icon>
