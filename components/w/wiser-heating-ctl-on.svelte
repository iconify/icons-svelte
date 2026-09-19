<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktoyf7b8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktoyf7b8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wiser-heating-ctl-on" {...props}></Icon>
