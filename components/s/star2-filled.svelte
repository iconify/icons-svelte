<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf7ewo7jq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mf7ewo7jq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:star2-filled" {...props}></Icon>
