<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqxcp5bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="zqxcp5bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:smile" {...props}></Icon>
