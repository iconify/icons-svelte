<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9378k2nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s9378k2nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:sushi-15" {...props}></Icon>
