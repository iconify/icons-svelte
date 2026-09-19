<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ped2ifbwy.css';
import '../../css/n/nppjnzgzv.css';
import '../../css/o/ow9vjabpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ped2ifbwy"/><rect class="nppjnzgzv"/><rect class="ow9vjabpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:vertical-align-bottom-filled" {...props}></Icon>
