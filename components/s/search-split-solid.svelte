<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko0725l_d.css';
import '../../css/f/fbeaqo8bl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ko0725l_d"/><path clip-rule="evenodd" class="fbeaqo8bl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:search-split-solid" {...props}></Icon>
