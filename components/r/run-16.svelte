<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx8-v0blk.css';
import '../../css/a/amiveibiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bx8-v0blk"/><path clip-rule="evenodd" class="amiveibiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:run-16" {...props}></Icon>
