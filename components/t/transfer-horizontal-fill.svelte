<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkmy43dwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkmy43dwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:transfer-horizontal-fill" {...props}></Icon>
