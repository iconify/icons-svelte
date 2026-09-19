<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amlfk0b-w.css';
import '../../css/m/myx56ib_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="amlfk0b-w"/><path class="myx56ib_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:stopwatch" {...props}></Icon>
