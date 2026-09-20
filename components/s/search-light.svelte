<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npb90acjk.css';
import '../../css/j/jy2_mcanx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npb90acjk"/><path class="jy2_mcanx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:search-light" {...props}></Icon>
