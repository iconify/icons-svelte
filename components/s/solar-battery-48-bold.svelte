<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o70_yqgvc.css';
import '../../css/m/m8ays9b5w.css';
import '../../css/i/i062jmb6q.css';
import '../../css/v/vjomywb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o70_yqgvc"/><path class="m8ays9b5w"/><path class="i062jmb6q"/><path class="vjomywb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-battery-48-bold" {...props}></Icon>
