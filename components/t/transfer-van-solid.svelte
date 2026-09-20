<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbqc9loyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lbqc9loyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:transfer-van-solid" {...props}></Icon>
