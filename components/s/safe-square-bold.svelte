<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycq6r6b3w.css';
import '../../css/a/a2habdbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycq6r6b3w"/><path clip-rule="evenodd" class="a2habdbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:safe-square-bold" {...props}></Icon>
