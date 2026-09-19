<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-g5sab0v.css';
import '../../css/l/lafymqbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o-g5sab0v"/><path class="lafymqbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:wallet-sharp" {...props}></Icon>
