<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk9pgpbto.css';
import '../../css/i/ik-axzblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bk9pgpbto"/><path class="ik-axzblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-arrow-down-exit-filled" {...props}></Icon>
