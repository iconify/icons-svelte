<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kilp2bv1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kilp2bv1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:upload-outlined" {...props}></Icon>
