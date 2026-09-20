<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to7tq6n3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="to7tq6n3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:x-oblique" {...props}></Icon>
