<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxz8lnubg.css';
import '../../css/e/eo0cog95z.css';
import '../../css/w/w8t6fkc8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxz8lnubg"/><path clip-rule="evenodd" class="eo0cog95z"/><path clip-rule="evenodd" class="w8t6fkc8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:turntable-bold-duotone" {...props}></Icon>
