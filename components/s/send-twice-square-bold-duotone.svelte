<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm03gzbnp.css';
import '../../css/f/fvqbw8bkl.css';
import '../../css/h/hcarscc_v.css';
import '../../css/l/lo9yp3b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path class="fvqbw8bkl"/><path class="hcarscc_v"/><path class="lo9yp3b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:send-twice-square-bold-duotone" {...props}></Icon>
