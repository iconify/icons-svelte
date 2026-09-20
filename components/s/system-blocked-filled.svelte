<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dun1dyudb.css';
import '../../css/j/j48cmzb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dun1dyudb"/><path class="j48cmzb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:system-blocked-filled" {...props}></Icon>
