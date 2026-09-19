<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt9rm4bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1344};
const content = `<path class="mt9rm4bdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:timeslot" {...props}></Icon>
