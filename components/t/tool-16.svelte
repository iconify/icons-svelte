<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5ni0d56x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y5ni0d56x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:tool-16" {...props}></Icon>
