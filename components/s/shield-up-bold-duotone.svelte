<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olgj_vbqo.css';
import '../../css/f/f1syezbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olgj_vbqo"/><path clip-rule="evenodd" class="f1syezbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-up-bold-duotone" {...props}></Icon>
