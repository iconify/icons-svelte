<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5odp7b0s.css';
import '../../css/a/asas4sbys.css';
import '../../css/q/qc5k0pb3l.css';
import '../../css/d/drd-mi95a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o5odp7b0s"/><path class="asas4sbys"/><path class="qc5k0pb3l"/><path class="drd-mi95a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:store-48" {...props}></Icon>
