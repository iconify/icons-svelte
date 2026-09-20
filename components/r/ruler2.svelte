<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s34lqgbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s34lqgbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ruler2" {...props}></Icon>
