<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jvtjbnueh.css';
import '../../css/n/n8uvj2-sw.css';
import '../../css/r/rw4xwmbye.css';
import '../../css/x/xxiqr7b7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jvtjbnueh"/><path class="n8uvj2-sw"/><path class="rw4xwmbye"/><path class="xxiqr7b7g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:turntable" {...props}></Icon>
