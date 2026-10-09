<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxklois4m.css';
import '../../css/t/t_7rprl1m.css';
import '../../css/u/ufn12ktbs.css';
import '../../css/u/uale--bkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dxklois4m"/><path class="t_7rprl1m"/><path class="ufn12ktbs"/><path class="uale--bkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:vehicle-to-grid-20-bold" {...props}></Icon>
