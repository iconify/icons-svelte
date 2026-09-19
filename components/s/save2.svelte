<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9rwoxb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s9rwoxb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:save2" {...props}></Icon>
