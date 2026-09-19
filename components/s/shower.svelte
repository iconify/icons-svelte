<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3rh6-bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p3rh6-bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:shower" {...props}></Icon>
