<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckq9ugjzq.css';
import '../../css/e/eadgts_vo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ckq9ugjzq"/><path class="eadgts_vo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:stop-twotone" {...props}></Icon>
