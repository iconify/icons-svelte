<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9-9gpbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9-9gpbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:ruler" {...props}></Icon>
