<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4j9h4bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":717};
const content = `<path class="q4j9h4bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:time" {...props}></Icon>
