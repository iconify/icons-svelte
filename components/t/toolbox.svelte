<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udjshvb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="udjshvb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:toolbox" {...props}></Icon>
