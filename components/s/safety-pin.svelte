<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t4vbohhei.css';
import '../../css/t/t-tdlib6h.css';
import '../../css/c/cff5u7gra.css';
import '../../css/u/unweze0-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="t4vbohhei"/><path class="t-tdlib6h"/><path class="cff5u7gra"/><path class="unweze0-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:safety-pin" {...props}></Icon>
