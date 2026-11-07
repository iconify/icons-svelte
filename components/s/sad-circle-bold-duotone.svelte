<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnb90nbxf.css';
import '../../css/c/ce8u24m5f.css';
import '../../css/g/go4rm8bar.css';
import '../../css/p/pydsljbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path class="ce8u24m5f"/><path class="go4rm8bar"/><path class="pydsljbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sad-circle-bold-duotone" {...props}></Icon>
