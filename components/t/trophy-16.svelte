<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsvk-rb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dsvk-rb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:trophy-16" {...props}></Icon>
