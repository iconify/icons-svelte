<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsds9abwl.css';
import '../../css/i/ixvh0acwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tsds9abwl"/><path clip-rule="evenodd" class="ixvh0acwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:volume-2-outline" {...props}></Icon>
