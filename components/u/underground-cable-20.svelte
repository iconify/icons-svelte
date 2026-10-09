<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubhg269_g.css';
import '../../css/h/hsrqj8b_j.css';
import '../../css/p/pt6rgpv5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ubhg269_g"/><path class="hsrqj8b_j"/><path class="pt6rgpv5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:underground-cable-20" {...props}></Icon>
