<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnha371ox.css';
import '../../css/o/o6hj5abyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnha371ox"/><path class="o6hj5abyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-rotate-ccw-filled" {...props}></Icon>
