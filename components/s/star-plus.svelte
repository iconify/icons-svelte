<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrr1f-bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrr1f-bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:star-plus" {...props}></Icon>
