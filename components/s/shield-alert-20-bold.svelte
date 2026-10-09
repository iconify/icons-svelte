<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdw3vx8xp.css';
import '../../css/j/jgxj3hb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fdw3vx8xp"/><path class="jgxj3hb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shield-alert-20-bold" {...props}></Icon>
