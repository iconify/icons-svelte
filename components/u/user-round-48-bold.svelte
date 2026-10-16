<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moyoz5fkv.css';
import '../../css/p/p5ne8n6_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="moyoz5fkv"/><path class="p5ne8n6_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-round-48-bold" {...props}></Icon>
