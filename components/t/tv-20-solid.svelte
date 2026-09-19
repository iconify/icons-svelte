<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kq-88ebqc.css';
import '../../css/v/v9ki5ibpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="kq-88ebqc"/><path clip-rule="evenodd" class="v9ki5ibpw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:tv-20-solid" {...props}></Icon>
