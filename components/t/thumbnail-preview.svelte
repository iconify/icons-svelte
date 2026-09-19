<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyyydmbfg.css';
import '../../css/l/lk--g1e_g.css';
import '../../css/n/noishdbbf.css';
import '../../css/c/cu3zp1biq.css';
import '../../css/a/av9l-sbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tyyydmbfg"/><path class="lk--g1e_g"/><path class="noishdbbf"/><path class="cu3zp1biq"/><path class="av9l-sbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:thumbnail-preview" {...props}></Icon>
