<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxjfcsudw.css';
import '../../css/q/q-qy_1ldb.css';
import '../../css/v/v0mgkb00e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xxjfcsudw"/><path class="q-qy_1ldb"/><path class="v0mgkb00e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:typeorm-wordmark" {...props}></Icon>
