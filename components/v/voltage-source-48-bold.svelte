<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe8f_eb4j.css';
import '../../css/z/z8jeaq2_u.css';
import '../../css/j/j-2pke6of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qe8f_eb4j"/><path class="z8jeaq2_u"/><path class="j-2pke6of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:voltage-source-48-bold" {...props}></Icon>
