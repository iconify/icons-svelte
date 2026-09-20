<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-n0_5b8w.css';
import '../../css/l/lwm0shbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-n0_5b8w"/><path clip-rule="evenodd" class="lwm0shbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:schedule-fill" {...props}></Icon>
