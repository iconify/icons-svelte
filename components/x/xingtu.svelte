<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6nfn3bmq.css';
import '../../css/d/d9itboj4b.css';
import '../../css/a/aqb2160dr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h6nfn3bmq"/><path class="d9itboj4b"/><path class="aqb2160dr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:xingtu" {...props}></Icon>
