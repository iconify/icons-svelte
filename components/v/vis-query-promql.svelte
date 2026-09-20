<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8s6xvu0y.css';
import '../../css/e/ed612wbnx.css';
import '../../css/o/o-g8_8o4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w8s6xvu0y"/><path class="ed612wbnx"/><path clip-rule="evenodd" class="o-g8_8o4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:vis-query-promql" {...props}></Icon>
