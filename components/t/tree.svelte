<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/da0su4uhx.css';
import '../../css/t/tfi0d09kv.css';
import '../../css/s/s5bjb7baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="da0su4uhx"/><path class="tfi0d09kv"/><path class="s5bjb7baj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:tree" {...props}></Icon>
