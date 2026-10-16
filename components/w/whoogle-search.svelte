<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6o3ktbcu.css';
import '../../css/w/wjyxzxbul.css';
import '../../css/y/yj4lhpb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1028,"height":254};
const content = `<path class="x6o3ktbcu"/><path class="wjyxzxbul"/><path class="yj4lhpb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:whoogle-search" {...props}></Icon>
