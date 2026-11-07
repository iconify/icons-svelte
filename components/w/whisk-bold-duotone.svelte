<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bji9ibcha.css';
import '../../css/b/boq_u9ond.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bji9ibcha"/><path class="boq_u9ond"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:whisk-bold-duotone" {...props}></Icon>
