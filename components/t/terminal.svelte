<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi2wt22zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gi2wt22zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:terminal" {...props}></Icon>
