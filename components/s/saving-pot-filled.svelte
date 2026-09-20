<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvpyx4bjk.css';
import '../../css/a/ac0sjm13i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvpyx4bjk"/><path class="ac0sjm13i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:saving-pot-filled" {...props}></Icon>
