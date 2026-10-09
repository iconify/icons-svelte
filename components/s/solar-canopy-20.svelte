<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceex6qbaz.css';
import '../../css/c/chgc5thhd.css';
import '../../css/h/hyns0sb6c.css';
import '../../css/d/ds_4hp33i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ceex6qbaz"/><path class="chgc5thhd"/><path class="hyns0sb6c"/><path class="ds_4hp33i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-canopy-20" {...props}></Icon>
