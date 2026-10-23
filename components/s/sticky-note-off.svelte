<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qij98ubos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qij98ubos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:sticky-note-off" {...props}></Icon>
