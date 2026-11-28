<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phkdd0b6a.css';
import '../../css/d/d0bxfnb3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phkdd0b6a secondary"/><path class="d0bxfnb3f primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:semicircle-duo" {...props}></Icon>
