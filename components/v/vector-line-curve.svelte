<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dytkoubrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dytkoubrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:vector-line-curve" {...props}></Icon>
