<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxkfan9rf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxkfan9rf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:slack" {...props}></Icon>
