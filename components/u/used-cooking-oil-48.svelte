<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqiw7wq1k.css';
import '../../css/u/u_7j5cbnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xqiw7wq1k"/><path class="u_7j5cbnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:used-cooking-oil-48" {...props}></Icon>
