<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o5dnc48bh.css';
import '../../css/e/em3y75frz.css';
import '../../css/p/pqc8yuf2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="o5dnc48bh"/><circle class="em3y75frz"/><path class="pqc8yuf2e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:unordered-list-filled" {...props}></Icon>
