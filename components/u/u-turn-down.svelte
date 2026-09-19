<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/x/x6nhvj-7w.css';
import '../../css/x/xupb65btz.css';
import '../../css/y/y525ptbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="x6nhvj-7w"/><path class="xupb65btz"/><circle transform="rotate(90 35 39)" class="y525ptbor"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:u-turn-down" {...props}></Icon>
