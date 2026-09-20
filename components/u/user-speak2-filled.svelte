<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/flhgcwu9s.css';
import '../../css/b/baqhphbbl.css';
import '../../css/e/eh69lwb0v.css';
import '../../css/a/aeuv7ifjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="flhgcwu9s"/><ellipse class="baqhphbbl"/><path clip-rule="evenodd" class="eh69lwb0v"/><path clip-rule="evenodd" class="aeuv7ifjx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user-speak2-filled" {...props}></Icon>
