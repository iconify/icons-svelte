<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/m/mbtf-g2sk.css';
import '../../css/f/fz2yxm-re.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mbtf-g2sk"/><path class="fz2yxm-re"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:square-brackets-ellipsis-right" {...props}></Icon>
