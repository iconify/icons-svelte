<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5-y49b9d.css';
import '../../css/b/bu7krvb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x5-y49b9d"/><path clip-rule="evenodd" class="bu7krvb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:task-past-16" {...props}></Icon>
