<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh4bwob4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kh4bwob4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:stairs-03" {...props}></Icon>
