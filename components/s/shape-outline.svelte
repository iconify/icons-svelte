<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zssm3ybnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zssm3ybnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-outline" {...props}></Icon>
