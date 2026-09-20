<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziyt1r3lp.css';
import '../../css/w/wel9mzd3v.css';
import '../../css/l/lw5zwnyrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ziyt1r3lp"/><path class="wel9mzd3v"/><path class="lw5zwnyrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sunwet" {...props}></Icon>
