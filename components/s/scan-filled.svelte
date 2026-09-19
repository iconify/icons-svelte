<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj0_tcbbp.css';
import '../../css/j/jz4jx24-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cj0_tcbbp"/><path class="jz4jx24-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:scan-filled" {...props}></Icon>
