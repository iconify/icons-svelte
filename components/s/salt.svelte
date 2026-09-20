<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb_5mrzpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tb_5mrzpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:salt" {...props}></Icon>
