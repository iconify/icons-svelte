<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zveyaixcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zveyaixcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:turn-right" {...props}></Icon>
