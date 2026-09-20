<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3e4w2dth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3e4w2dth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:subscript" {...props}></Icon>
