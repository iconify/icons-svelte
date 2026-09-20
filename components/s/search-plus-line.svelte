<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft1jb2qms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft1jb2qms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:search-plus-line" {...props}></Icon>
