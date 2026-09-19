<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqqq5obas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqqq5obas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:send" {...props}></Icon>
