<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iiz4a2b8e.css';
import '../../css/q/qat5inhjr.css';
import '../../css/s/shtujqapo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iiz4a2b8e"/><circle class="qat5inhjr"/><path class="shtujqapo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:suwayomi-dark" {...props}></Icon>
