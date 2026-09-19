<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnwn4yowi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qnwn4yowi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:unity" {...props}></Icon>
