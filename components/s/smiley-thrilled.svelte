<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es0y-zp9y.css';
import '../../css/p/po5fh-7sr.css';
import '../../css/c/cwoolsbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="es0y-zp9y"/><path class="po5fh-7sr"/><path class="cwoolsbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:smiley-thrilled" {...props}></Icon>
