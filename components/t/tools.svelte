<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gimnuqufm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gimnuqufm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:tools" {...props}></Icon>
