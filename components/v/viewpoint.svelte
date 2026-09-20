<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukdgz6b1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ukdgz6b1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:viewpoint" {...props}></Icon>
