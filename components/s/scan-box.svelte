<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1acneb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1acneb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:scan-box" {...props}></Icon>
