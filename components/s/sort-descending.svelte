<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo1bv0flp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wo1bv0flp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:sort-descending" {...props}></Icon>
