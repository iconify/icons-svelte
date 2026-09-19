<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adrsww8cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adrsww8cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:tired" {...props}></Icon>
