<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-5j89ong.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-5j89ong"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tennis-ball-round" {...props}></Icon>
