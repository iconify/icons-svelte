<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1gf5ddcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1gf5ddcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:swimming-round" {...props}></Icon>
