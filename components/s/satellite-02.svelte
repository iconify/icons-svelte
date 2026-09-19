<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz8iv6yzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gz8iv6yzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:satellite-02" {...props}></Icon>
