<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr2cl1avx.css';
import '../../css/y/y_dpcj0im.css';
import '../../css/e/eb25nslsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kr2cl1avx"/><path class="y_dpcj0im"/><path class="eb25nslsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tree-20" {...props}></Icon>
