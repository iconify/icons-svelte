<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/q/qo5tdhb3o.css';
import '../../css/i/iyml-1f6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="videocam-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="qo5tdhb3o"/><path class="iyml-1f6i"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:videocam-outline" {...props}></Icon>
