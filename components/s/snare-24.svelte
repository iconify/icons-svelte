<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbq2xpfpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vbq2xpfpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:snare-24" {...props}></Icon>
