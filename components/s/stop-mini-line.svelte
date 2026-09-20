<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7g73ppkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7g73ppkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:stop-mini-line" {...props}></Icon>
