<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in4eu7odv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="in4eu7odv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:windmill" {...props}></Icon>
