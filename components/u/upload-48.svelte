<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upy-ybcph.css';
import '../../css/i/iw2o35bsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="upy-ybcph"/><path class="iw2o35bsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:upload-48" {...props}></Icon>
