<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quzl6dbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="quzl6dbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:set-intersection" {...props}></Icon>
