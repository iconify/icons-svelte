<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8okp_dga.css';
import '../../css/o/o5ofv024l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8okp_dga"/><path class="o5ofv024l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:tools-kitchen-scale-bold" {...props}></Icon>
