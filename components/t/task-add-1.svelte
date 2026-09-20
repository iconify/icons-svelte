<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udedc6b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udedc6b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:task-add-1" {...props}></Icon>
