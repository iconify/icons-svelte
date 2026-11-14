<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9igf18py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9igf18py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ubiquiti-ap" {...props}></Icon>
