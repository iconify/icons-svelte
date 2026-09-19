<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qiasnzb7m.css';
import '../../css/k/kai3g5bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qiasnzb7m"/><path class="kai3g5bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:taxi" {...props}></Icon>
