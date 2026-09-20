<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yse31pbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yse31pbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ruler" {...props}></Icon>
