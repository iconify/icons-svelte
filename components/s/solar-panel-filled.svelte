<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy00zfmuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xy00zfmuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:solar-panel-filled" {...props}></Icon>
