<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzk9z5ksk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="hzk9z5ksk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-horizontal-stairs-descend-left" {...props}></Icon>
