<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubgy9z47q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ubgy9z47q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:scooter-15" {...props}></Icon>
