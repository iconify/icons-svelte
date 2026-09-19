<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-pezac1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a-pezac1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:uploadalt" {...props}></Icon>
