<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b76a-v8pr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b76a-v8pr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:tic-tac-toe" {...props}></Icon>
