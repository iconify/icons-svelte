<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay2u52b1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ay2u52b1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:shape-half-circle" {...props}></Icon>
