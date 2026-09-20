<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zko6-tb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zko6-tb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:row-insert-bottom" {...props}></Icon>
