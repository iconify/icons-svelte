<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok-5cd9qq.css';
import '../../css/t/tjtae605g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ok-5cd9qq"/><path clip-rule="evenodd" class="tjtae605g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:scroll-down-2" {...props}></Icon>
