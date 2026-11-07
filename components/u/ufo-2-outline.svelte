<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkhl62fff.css';
import '../../css/j/jftj_8bfk.css';
import '../../css/e/elc-1sb2u.css';
import '../../css/d/dq5_8vb3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkhl62fff"/><path class="jftj_8bfk"/><path class="elc-1sb2u"/><path clip-rule="evenodd" class="dq5_8vb3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ufo-2-outline" {...props}></Icon>
