<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v538bx.css';
import '../../css/c/cfdtzv.css';
import '../../css/b/botfzx.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-1.css';
import '../../css/f/fade-to-1.css';
import '../../css/d/d--8d_6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGL9Ab9dwT"><path class="v538bx"/><path class="cfdtzv"/></mask></defs><path mask="url(#SVGL9Ab9dwT)" class="botfzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:youtube-filled" {...props}></Icon>
