<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip7p42btd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ip7p42btd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:whitespace" {...props}></Icon>
