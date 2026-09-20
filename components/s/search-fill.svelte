<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uft75ab9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uft75ab9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:search-fill" {...props}></Icon>
