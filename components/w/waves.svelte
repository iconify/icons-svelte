<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqfn82bnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqfn82bnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:waves" {...props}></Icon>
