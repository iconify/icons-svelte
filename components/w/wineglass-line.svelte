<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_78p0pql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_78p0pql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wineglass-line" {...props}></Icon>
