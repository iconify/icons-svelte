<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_ck-kb7o.css';
import '../../css/k/kyehcvbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f_ck-kb7o"/><path class="kyehcvbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:virtual-private-cloud-alt" {...props}></Icon>
