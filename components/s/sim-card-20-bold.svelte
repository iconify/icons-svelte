<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf-lmqboi.css';
import '../../css/c/c8c_oybxb.css';
import '../../css/v/v--izksva.css';
import '../../css/v/vrqg2kbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lf-lmqboi"/><path class="c8c_oybxb"/><path class="v--izksva"/><path class="vrqg2kbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sim-card-20-bold" {...props}></Icon>
