<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2027-biw.css';
import '../../css/l/lgeglqbcu.css';
import '../../css/z/zy6utib6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p2027-biw"/><path class="lgeglqbcu"/><path class="zy6utib6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:zeabur" {...props}></Icon>
