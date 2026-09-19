<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mabaapu1g.css';
import '../../css/h/hhh60ljkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mabaapu1g"/><path class="hhh60ljkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-subtract" {...props}></Icon>
