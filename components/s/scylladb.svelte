<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bezqb2i-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bezqb2i-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:scylladb" {...props}></Icon>
