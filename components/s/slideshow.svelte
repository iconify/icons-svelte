<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pglqq_f1q.css';
import '../../css/t/trfu-vbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pglqq_f1q"/><path class="trfu-vbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:slideshow" {...props}></Icon>
