<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbfjszvql.css';
import '../../css/q/qstm5aclq.css';
import '../../css/u/u9olyabjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="tbfjszvql"/><path class="qstm5aclq"/><path class="u9olyabjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:websheet" {...props}></Icon>
