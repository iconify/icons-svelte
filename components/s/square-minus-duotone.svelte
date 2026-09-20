<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d639svbxj.css';
import '../../css/t/t3t9a1dtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d639svbxj"/><path class="t3t9a1dtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:square-minus-duotone" {...props}></Icon>
