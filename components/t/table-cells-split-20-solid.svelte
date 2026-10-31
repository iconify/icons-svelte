<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3jp-_2dc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="s3jp-_2dc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:table-cells-split-20-solid" {...props}></Icon>
