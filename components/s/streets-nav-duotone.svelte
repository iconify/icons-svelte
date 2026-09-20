<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a_kkd2brg.css';
import '../../css/g/g73wvxbdb.css';
import '../../css/a/a3cqnpbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a_kkd2brg"/><path class="g73wvxbdb"/><path class="a3cqnpbsa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:streets-nav-duotone" {...props}></Icon>
