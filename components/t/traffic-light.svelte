<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/lzvv6ryeo.css';
import '../../css/p/piq7nbcjz.css';
import '../../css/o/od0wt3bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="lzvv6ryeo"/><path class="piq7nbcjz"/><path class="od0wt3bac"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:traffic-light" {...props}></Icon>
