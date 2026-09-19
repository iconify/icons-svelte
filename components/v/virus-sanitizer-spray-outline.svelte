<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oiz0jrbek.css';
import '../../css/b/b2evgybnf.css';
import '../../css/u/uxcp4yfkp.css';
import '../../css/z/z23feqc8q.css';
import '../../css/q/qmzhmtbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="oiz0jrbek"/><path class="b2evgybnf"/><path class="uxcp4yfkp"/><path clip-rule="evenodd" class="z23feqc8q"/><path class="qmzhmtbqy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:virus-sanitizer-spray-outline" {...props}></Icon>
