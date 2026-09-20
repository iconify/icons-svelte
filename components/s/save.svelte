<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm53oh82d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pm53oh82d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:save" {...props}></Icon>
