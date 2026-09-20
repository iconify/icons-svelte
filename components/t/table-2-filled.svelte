<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_nj2bbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_nj2bbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:table-2-filled" {...props}></Icon>
