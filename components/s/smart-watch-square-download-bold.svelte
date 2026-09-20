<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uov_tcc-r.css';
import '../../css/r/rfvufj5tw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uov_tcc-r"/><path class="rfvufj5tw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:smart-watch-square-download-bold" {...props}></Icon>
