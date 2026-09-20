<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7v60o3qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c7v60o3qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shelf-remix" {...props}></Icon>
