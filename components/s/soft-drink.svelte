<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u9r_f26yz.css';
import '../../css/a/a4fa86ant.css';
import '../../css/h/h55fdbcqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="u9r_f26yz"/><path class="a4fa86ant"/><path class="h55fdbcqv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:soft-drink" {...props}></Icon>
