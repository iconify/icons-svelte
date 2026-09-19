<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djw0pcgoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djw0pcgoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:shield" {...props}></Icon>
