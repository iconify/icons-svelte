<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck-suz5qq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck-suz5qq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sd-card-line" {...props}></Icon>
