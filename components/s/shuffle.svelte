<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl9h3zbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zl9h3zbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:shuffle" {...props}></Icon>
