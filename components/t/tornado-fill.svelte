<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8nghhbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8nghhbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tornado-fill" {...props}></Icon>
