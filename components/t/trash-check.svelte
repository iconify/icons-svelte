<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jju9kab-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jju9kab-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:trash-check" {...props}></Icon>
