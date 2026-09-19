<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtm-4pbpn.css';
import '../../css/d/dh1shqbdr.css';
import '../../css/u/usdnfabrq.css';
import '../../css/z/ze7q12bdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gtm-4pbpn"/><path class="dh1shqbdr"/><path class="usdnfabrq"/><path class="ze7q12bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:scikitlearn" {...props}></Icon>
