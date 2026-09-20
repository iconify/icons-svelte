<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuzrz4s5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-3};
const content = `<path class="nuzrz4s5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:volume" {...props}></Icon>
