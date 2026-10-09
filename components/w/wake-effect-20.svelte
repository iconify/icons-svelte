<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgz8hfjwl.css';
import '../../css/f/f55k4bcmg.css';
import '../../css/m/ma4byl76i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pgz8hfjwl"/><path class="f55k4bcmg"/><path class="ma4byl76i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wake-effect-20" {...props}></Icon>
