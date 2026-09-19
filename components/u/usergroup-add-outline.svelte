<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmeb-_bqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lmeb-_bqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:usergroup-add-outline" {...props}></Icon>
