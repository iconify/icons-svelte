<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1e6tq2-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1e6tq2-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tomato" {...props}></Icon>
