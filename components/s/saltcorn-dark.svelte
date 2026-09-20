<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrlw-04kw.css';
import '../../css/l/l3azjz_az.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rrlw-04kw"/><path class="l3azjz_az"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:saltcorn-dark" {...props}></Icon>
