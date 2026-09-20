<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9usjft2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9usjft2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:route-line" {...props}></Icon>
