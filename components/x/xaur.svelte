<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzgev3bud.css';
import '../../css/m/megg44b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzgev3bud"/><path class="megg44b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xaur" {...props}></Icon>
