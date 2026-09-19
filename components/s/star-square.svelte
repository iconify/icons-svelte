<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-wgyugil.css';
import '../../css/q/qlgozrxrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-wgyugil"/><path class="qlgozrxrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:star-square" {...props}></Icon>
