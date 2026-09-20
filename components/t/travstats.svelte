<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob9sxvbzl.css';
import '../../css/z/zfyfngbdb.css';
import '../../css/l/lnqbgixxr.css';
import '../../css/i/if99olb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ob9sxvbzl"/><path class="zfyfngbdb"/><path class="lnqbgixxr"/><path class="if99olb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:travstats" {...props}></Icon>
