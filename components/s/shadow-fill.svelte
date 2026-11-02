<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coe30gbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="coe30gbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shadow-fill" {...props}></Icon>
