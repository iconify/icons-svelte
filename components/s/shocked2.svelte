<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9-op4kkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b9-op4kkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:shocked2" {...props}></Icon>
