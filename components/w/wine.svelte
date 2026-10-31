<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rny_ojbdv.css';
import '../../css/j/j01iy8biv.css';
import '../../css/g/g-k4n4b7m.css';
import '../../css/e/ef99ei22g.css';
import '../../css/e/e3sz6nb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rny_ojbdv"/><path class="j01iy8biv"/><path class="g-k4n4b7m"/><path class="ef99ei22g"/><path class="e3sz6nb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:wine" {...props}></Icon>
