<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2vikjncm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r2vikjncm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:step-backward-outlined" {...props}></Icon>
