<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc0r-sbyi.css';
import '../../css/q/q5jdzcb9m.css';
import '../../css/c/cf-nt9u3d.css';
import '../../css/z/zb1dbob6a.css';
import '../../css/o/o9sudkbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lc0r-sbyi"/><path class="q5jdzcb9m"/><path class="cf-nt9u3d"/><path class="zb1dbob6a"/><path class="o9sudkbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:whale" {...props}></Icon>
