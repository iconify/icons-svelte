<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfdmfubxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfdmfubxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sort-alpha-solid" {...props}></Icon>
