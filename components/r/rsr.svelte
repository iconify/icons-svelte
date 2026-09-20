<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnxgwlb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mnxgwlb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rsr" {...props}></Icon>
