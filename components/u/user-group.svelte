<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oop7cv_mf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oop7cv_mf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:user-group" {...props}></Icon>
