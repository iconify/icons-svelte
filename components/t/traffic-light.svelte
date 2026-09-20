<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm7z09bpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm7z09bpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:traffic-light" {...props}></Icon>
