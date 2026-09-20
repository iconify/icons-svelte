<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drrty8bwe.css';
import '../../css/d/dg2iadbgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drrty8bwe"/><path clip-rule="evenodd" class="dg2iadbgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:unlocked-2" {...props}></Icon>
