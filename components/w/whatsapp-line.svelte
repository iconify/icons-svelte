<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azosf2fdp.css';
import '../../css/f/folb2v_pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azosf2fdp"/><path clip-rule="evenodd" class="folb2v_pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:whatsapp-line" {...props}></Icon>
