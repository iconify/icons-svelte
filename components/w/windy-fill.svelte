<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfnsi60mx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfnsi60mx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:windy-fill" {...props}></Icon>
