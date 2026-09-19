<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4sth9bce.css';
import '../../css/k/kttmg1byv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="d4sth9bce"/><path class="kttmg1byv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:upload-cloud" {...props}></Icon>
