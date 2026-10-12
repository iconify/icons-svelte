<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zizp4pbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zizp4pbtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:sine" {...props}></Icon>
