<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdr11pzqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kdr11pzqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:staples" {...props}></Icon>
