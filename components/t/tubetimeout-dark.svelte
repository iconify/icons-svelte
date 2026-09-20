<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icbjugb1y.css';
import '../../css/d/dv8e4qb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="icbjugb1y"/><path class="dv8e4qb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tubetimeout-dark" {...props}></Icon>
