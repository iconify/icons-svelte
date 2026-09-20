<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuktf_bzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cuktf_bzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:upwork-fill" {...props}></Icon>
