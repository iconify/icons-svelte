<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f77o91b_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f77o91b_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:table-lamp" {...props}></Icon>
