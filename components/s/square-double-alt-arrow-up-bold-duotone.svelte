<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk8_knd5w.css';
import '../../css/l/lpsml7sns.css';
import '../../css/h/h1p473pfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk8_knd5w"/><path class="lpsml7sns"/><path class="h1p473pfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-double-alt-arrow-up-bold-duotone" {...props}></Icon>
