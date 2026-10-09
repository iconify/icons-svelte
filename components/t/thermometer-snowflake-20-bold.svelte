<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtrh8db_y.css';
import '../../css/x/xz6a5cb-u.css';
import '../../css/b/bbfi5pr6q.css';
import '../../css/f/f0ef-nfej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mtrh8db_y"/><path class="xz6a5cb-u"/><path class="bbfi5pr6q"/><path class="f0ef-nfej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermometer-snowflake-20-bold" {...props}></Icon>
