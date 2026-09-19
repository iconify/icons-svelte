<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj_3yzbcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oj_3yzbcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:trash-bin-outline" {...props}></Icon>
