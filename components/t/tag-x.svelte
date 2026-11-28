<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptk6-3vvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ptk6-3vvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:tag-x" {...props}></Icon>
