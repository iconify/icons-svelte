<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6rueab4y.css';
import '../../css/k/kcx9ch0qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="e6rueab4y"/><path class="kcx9ch0qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:ukraine" {...props}></Icon>
