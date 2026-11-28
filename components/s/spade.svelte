<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak0d4abdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ak0d4abdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:spade" {...props}></Icon>
