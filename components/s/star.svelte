<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvk9hvouj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvk9hvouj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:star" {...props}></Icon>
