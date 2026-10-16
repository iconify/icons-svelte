<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i42iihbqt.css';
import '../../css/l/l4p0db2vd.css';
import '../../css/h/h3_74q9gb.css';
import '../../css/h/h95v30bmf.css';
import '../../css/q/qdytrdbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i42iihbqt"/><path class="l4p0db2vd"/><path class="h3_74q9gb"/><path class="h95v30bmf"/><path class="qdytrdbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermostat-check-48" {...props}></Icon>
