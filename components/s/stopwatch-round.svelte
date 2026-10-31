<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-70y339k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-70y339k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:stopwatch-round" {...props}></Icon>
