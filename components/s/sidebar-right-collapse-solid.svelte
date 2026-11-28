<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi83habxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zi83habxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sidebar-right-collapse-solid" {...props}></Icon>
