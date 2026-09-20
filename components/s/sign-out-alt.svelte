<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkrt_z8cs.css';
import '../../css/k/kazlm8w_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkrt_z8cs"/><path class="kazlm8w_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:sign-out-alt" {...props}></Icon>
