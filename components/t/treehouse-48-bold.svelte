<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqbe_cc_j.css';
import '../../css/c/cot5v44oq.css';
import '../../css/b/b00qdxb4c.css';
import '../../css/z/zwi9klbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jqbe_cc_j"/><path class="cot5v44oq"/><path class="b00qdxb4c"/><path class="zwi9klbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:treehouse-48-bold" {...props}></Icon>
