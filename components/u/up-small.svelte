<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukkq_py3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ukkq_py3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:up-small" {...props}></Icon>
