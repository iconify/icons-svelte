<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qetnckbkp.css';
import '../../css/k/kgks08b4h.css';
import '../../css/u/ubw9i8bzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qetnckbkp"/><path class="kgks08b4h"/><path class="ubw9i8bzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:toykotower" {...props}></Icon>
