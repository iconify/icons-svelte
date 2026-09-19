<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f41sj1dgi.css';
import '../../css/o/o9f842q3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f41sj1dgi"/><path class="o9f842q3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:spa" {...props}></Icon>
