<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj_kz5bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kj_kz5bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:snowflake-line" {...props}></Icon>
