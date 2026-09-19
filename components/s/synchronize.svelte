<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrfs08bjl.css';
import '../../css/h/h999mzfzw.css';
import '../../css/p/pu-os2bbu.css';
import '../../css/c/c5wpdllfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qrfs08bjl"/><path class="h999mzfzw"/><path class="pu-os2bbu"/><path class="c5wpdllfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:synchronize" {...props}></Icon>
