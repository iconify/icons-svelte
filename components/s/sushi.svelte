<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxdb5_76z.css';
import '../../css/m/mq0bfxeqb.css';
import '../../css/f/fy61_f-vm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxdb5_76z"/><path clip-rule="evenodd" class="mq0bfxeqb"/><path class="fy61_f-vm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:sushi" {...props}></Icon>
