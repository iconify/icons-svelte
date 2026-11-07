<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-yckdk2x.css';
import '../../css/k/kdm4lcb3e.css';
import '../../css/s/seqcy-7oq.css';
import '../../css/l/lri0zsbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-yckdk2x"/><path class="kdm4lcb3e"/><path class="seqcy-7oq"/><path class="lri0zsbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wi-fi-bold" {...props}></Icon>
