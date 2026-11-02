<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frc6tjsrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frc6tjsrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:twitter-fill" {...props}></Icon>
