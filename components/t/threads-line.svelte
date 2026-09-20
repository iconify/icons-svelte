<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8asrggrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8asrggrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:threads-line" {...props}></Icon>
