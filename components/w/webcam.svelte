<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/g/g1st-obsh.css';
import '../../css/z/zv6cqnbnp.css';
import '../../css/p/pvue1ejtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="g1st-obsh"/><circle class="zv6cqnbnp"/><path class="pvue1ejtp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:webcam" {...props}></Icon>
