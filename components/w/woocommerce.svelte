<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1ph6jbci.css';
import '../../css/s/st682lbcm.css';
import '../../css/u/us9ytuuie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="m1ph6jbci"/><path class="st682lbcm"/><path class="us9ytuuie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:woocommerce" {...props}></Icon>
