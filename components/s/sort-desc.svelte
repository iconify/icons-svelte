<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6vn6g5-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6vn6g5-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:sort-desc" {...props}></Icon>
