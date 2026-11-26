<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt7tskbwm.css';
import '../../css/o/ol788r1ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="nt7tskbwm"/><path class="ol788r1ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:statuspage" {...props}></Icon>
