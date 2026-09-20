<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpu57nboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpu57nboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:telescope-24" {...props}></Icon>
