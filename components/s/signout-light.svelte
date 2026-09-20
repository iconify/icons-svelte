<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5g1yj-up.css';
import '../../css/v/vv-w0sjvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5g1yj-up"/><path class="vv-w0sjvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:signout-light" {...props}></Icon>
