<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgx5q2o1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path clip-rule="evenodd" class="tgx5q2o1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:targon" {...props}></Icon>
