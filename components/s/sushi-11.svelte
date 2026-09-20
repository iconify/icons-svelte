<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9x4zmb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="s9x4zmb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:sushi-11" {...props}></Icon>
