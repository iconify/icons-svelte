<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmcg74msr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmcg74msr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:whistle-fill" {...props}></Icon>
