<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6jb2xjee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6jb2xjee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:tree-pine" {...props}></Icon>
