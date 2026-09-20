<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b54c3v5wl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="b54c3v5wl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:shadow" {...props}></Icon>
