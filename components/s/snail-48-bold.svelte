<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pedr4_bjp.css';
import '../../css/f/f6h5kcc6e.css';
import '../../css/f/fw_ltzhjf.css';
import '../../css/i/iztk93-oh.css';
import '../../css/f/fq2ob0irn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pedr4_bjp"/><path class="f6h5kcc6e"/><path class="fw_ltzhjf"/><path class="iztk93-oh"/><path class="fq2ob0irn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:snail-48-bold" {...props}></Icon>
