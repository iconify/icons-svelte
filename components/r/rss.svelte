<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcw5atb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcw5atb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:rss" {...props}></Icon>
