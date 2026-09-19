<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is3xbuo4a.css';
import '../../css/a/a6vuirsuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="is3xbuo4a"/><path class="a6vuirsuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:trash-x" {...props}></Icon>
