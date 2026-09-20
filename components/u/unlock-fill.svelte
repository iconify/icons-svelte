<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kybc7u4rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kybc7u4rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:unlock-fill" {...props}></Icon>
