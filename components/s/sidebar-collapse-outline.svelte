<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q61-t8b_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q61-t8b_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:sidebar-collapse-outline" {...props}></Icon>
