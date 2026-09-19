<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz2ov7bmp.css';
import '../../css/p/p12bzlbrl.css';
import '../../css/j/j24ii1bme.css';
import '../../css/b/bzre8l_um.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="kz2ov7bmp"/><path class="p12bzlbrl"/><path class="j24ii1bme"/><path class="bzre8l_um"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:vsphere-wordmark" {...props}></Icon>
