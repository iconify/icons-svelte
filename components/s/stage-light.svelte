<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jedb1uq9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jedb1uq9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:stage-light" {...props}></Icon>
