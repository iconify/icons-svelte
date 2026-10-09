<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re49p_baz.css';
import '../../css/s/sxankrbtm.css';
import '../../css/a/ahm30acpt.css';
import '../../css/r/ruodnwngh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="re49p_baz"/><path class="sxankrbtm"/><path class="ahm30acpt"/><path class="ruodnwngh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:vehicle-to-grid-48-bold" {...props}></Icon>
