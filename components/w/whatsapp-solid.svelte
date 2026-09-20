<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxpwkkx4b.css';
import '../../css/c/cxrhsobiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="oxpwkkx4b"/><path clip-rule="evenodd" class="cxrhsobiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:whatsapp-solid" {...props}></Icon>
