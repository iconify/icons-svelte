<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5s7lcbme.css';
import '../../css/p/phlx78bqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5s7lcbme"/><path class="phlx78bqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tag-state-filled" {...props}></Icon>
