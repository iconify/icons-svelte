<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtx8mq7hg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtx8mq7hg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-split-vertical-solid" {...props}></Icon>
