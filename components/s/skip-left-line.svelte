<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3ldsk1xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3ldsk1xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:skip-left-line" {...props}></Icon>
