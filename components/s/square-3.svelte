<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inuaq7k-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inuaq7k-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:square-3" {...props}></Icon>
