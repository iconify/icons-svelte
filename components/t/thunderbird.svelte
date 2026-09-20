<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv9lud5-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rv9lud5-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:thunderbird" {...props}></Icon>
