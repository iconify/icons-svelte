<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khi8ekbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khi8ekbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sort-ascending-line" {...props}></Icon>
