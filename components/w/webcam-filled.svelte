<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_vsq7l3i.css';
import '../../css/o/o5v0p5v_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_vsq7l3i"/><path clip-rule="evenodd" class="o5v0p5v_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:webcam-filled" {...props}></Icon>
