<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko_c4j18e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ko_c4j18e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:volume-off-fill" {...props}></Icon>
