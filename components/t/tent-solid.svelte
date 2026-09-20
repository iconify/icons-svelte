<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi7s_kbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi7s_kbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:tent-solid" {...props}></Icon>
