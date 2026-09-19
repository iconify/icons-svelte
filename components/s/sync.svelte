<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqyji8tcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jqyji8tcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:sync" {...props}></Icon>
