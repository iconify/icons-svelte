<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk7_6xv2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lk7_6xv2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-arrow-right-outline" {...props}></Icon>
