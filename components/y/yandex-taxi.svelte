<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pt72orbxr.css';
import '../../css/y/y6z1gibnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":141,"height":30};
const content = `<g class="bi12bsetm"><path class="pt72orbxr"/><path class="y6z1gibnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:yandex-taxi" {...props}></Icon>
