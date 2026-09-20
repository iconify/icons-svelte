<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtdsctbtj.css';
import '../../css/w/w6qwevbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtdsctbtj"/><path class="w6qwevbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:search-error-filled" {...props}></Icon>
