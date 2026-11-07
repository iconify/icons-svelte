<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-fn14bsx.css';
import '../../css/r/rzfigt_wj.css';
import '../../css/n/nv0ks132c.css';
import '../../css/d/dpktspbaa.css';
import '../../css/s/s8kjxnw5q.css';
import '../../css/g/gvx018bix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-fn14bsx"/><path clip-rule="evenodd" class="rzfigt_wj"/><path clip-rule="evenodd" class="nv0ks132c"/><path class="dpktspbaa"/><path class="s8kjxnw5q"/><path class="gvx018bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:vanity-bold-duotone" {...props}></Icon>
