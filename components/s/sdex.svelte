<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp06xm10d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qp06xm10d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:sdex" {...props}></Icon>
