<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtm_fmbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mtm_fmbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:wallet-fill" {...props}></Icon>
