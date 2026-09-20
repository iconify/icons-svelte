<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj8i9n62v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sj8i9n62v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:task-add" {...props}></Icon>
