<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnm3l5bqe.css';
import '../../css/e/ehym_vpmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lnm3l5bqe"/><path class="ehym_vpmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wheelchair-48" {...props}></Icon>
