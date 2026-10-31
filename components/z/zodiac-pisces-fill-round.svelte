<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utk1-nb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utk1-nb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zodiac-pisces-fill-round" {...props}></Icon>
