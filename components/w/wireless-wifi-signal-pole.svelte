<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/emswq_b0d.css';
import '../../css/o/o3s8st4ef.css';
import '../../css/y/yiijok71l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="emswq_b0d"/><path class="o3s8st4ef"/><path class="yiijok71l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:wireless-wifi-signal-pole" {...props}></Icon>
