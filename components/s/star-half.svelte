<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd6uv7bdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sd6uv7bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:star-half" {...props}></Icon>
