<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfsusyb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfsusyb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:voicemail-filled" {...props}></Icon>
