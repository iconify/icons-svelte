<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f041-1cwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f041-1cwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:search-dollar-remix" {...props}></Icon>
