<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykm2u3fal.css';
import '../../css/a/alh4zcbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykm2u3fal"/><path clip-rule="evenodd" class="alh4zcbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shield-keyhole-filled" {...props}></Icon>
