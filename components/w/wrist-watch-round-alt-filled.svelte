<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nldaqvbfh.css';
import '../../css/g/g4qvddbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nldaqvbfh"/><path class="g4qvddbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wrist-watch-round-alt-filled" {...props}></Icon>
