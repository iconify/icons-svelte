<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6evqk7gs.css';
import '../../css/a/a7r2o1pkb.css';
import '../../css/u/uj188tbka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6evqk7gs"/><path clip-rule="evenodd" class="a7r2o1pkb"/><path class="uj188tbka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smart-speaker-bold-duotone" {...props}></Icon>
