<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-vnpwnbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-vnpwnbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:vertical-distribution-center" {...props}></Icon>
