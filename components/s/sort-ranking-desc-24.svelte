<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1ds-6sfp.css';
import '../../css/p/p_sp1no_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1ds-6sfp"/><path clip-rule="evenodd" class="p_sp1no_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:sort-ranking-desc-24" {...props}></Icon>
