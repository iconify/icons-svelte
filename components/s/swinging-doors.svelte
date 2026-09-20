<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6uuk4btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q6uuk4btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:swinging-doors" {...props}></Icon>
