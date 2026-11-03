<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8a4m0b2a.css';
import '../../css/h/hjzkjwhbs.css';
import '../../css/p/poazbeb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="k8a4m0b2a"/><path class="hjzkjwhbs"/><path class="poazbeb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:xampp" {...props}></Icon>
