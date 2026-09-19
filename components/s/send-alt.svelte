<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h09x_ioqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h09x_ioqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:send-alt" {...props}></Icon>
