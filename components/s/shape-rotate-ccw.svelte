<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnha371ox.css';
import '../../css/z/zbsurkc7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b xnha371ox"/><path class="b zbsurkc7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-rotate-ccw" {...props}></Icon>
