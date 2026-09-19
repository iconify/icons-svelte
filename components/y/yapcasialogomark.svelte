<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9a067bgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":550,"height":720};
const content = `<path class="a9a067bgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:yapcasialogomark" {...props}></Icon>
