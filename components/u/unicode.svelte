<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c88zuab5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c88zuab5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:unicode" {...props}></Icon>
