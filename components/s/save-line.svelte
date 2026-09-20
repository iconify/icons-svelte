<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmzhqqbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmzhqqbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:save-line" {...props}></Icon>
