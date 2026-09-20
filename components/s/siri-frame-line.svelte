<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjr9i_a7v.css';
import '../../css/p/pz9kr7bph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="jjr9i_a7v"/><path class="pz9kr7bph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:siri-frame-line" {...props}></Icon>
