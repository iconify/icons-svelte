<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_3vfwbgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_3vfwbgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:sort-alt-line" {...props}></Icon>
