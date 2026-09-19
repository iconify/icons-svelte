<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/y9ra9v_nc.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/m/mt1kbjbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="y9ra9v_nc"/><circle class="shu3xdl9q"/><path class="mt1kbjbkl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sphere" {...props}></Icon>
