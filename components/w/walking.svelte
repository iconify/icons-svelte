<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jve6oc-3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":717};
const content = `<path class="jve6oc-3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:walking" {...props}></Icon>
