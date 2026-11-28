<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o447g3b3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o447g3b3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:wand" {...props}></Icon>
