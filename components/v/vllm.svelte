<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb2zfhboo.css';
import '../../css/k/k7g135buj.css';
import '../../css/o/ox2d_gpql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kb2zfhboo"/><path class="k7g135buj"/><path class="ox2d_gpql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vllm" {...props}></Icon>
