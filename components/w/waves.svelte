<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o17j_ibqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="o17j_ibqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:waves" {...props}></Icon>
