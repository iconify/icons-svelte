<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezk93g3ho.css';
import '../../css/b/b2b32nzwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezk93g3ho"/><path class="b2b32nzwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:waterdrop-bold-duotone" {...props}></Icon>
