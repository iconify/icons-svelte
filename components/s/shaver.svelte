<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/p/pqvkjslfz.css';
import '../../css/j/jjiany4ql.css';
import '../../css/q/qxq43kb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="pqvkjslfz"/><path class="jjiany4ql"/><path class="qxq43kb0f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:shaver" {...props}></Icon>
