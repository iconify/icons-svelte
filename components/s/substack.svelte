<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px37m5f4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="px37m5f4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:substack" {...props}></Icon>
