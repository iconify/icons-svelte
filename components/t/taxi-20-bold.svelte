<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy1qryb3w.css';
import '../../css/f/fd6b2rb5y.css';
import '../../css/p/pk3rcgb0u.css';
import '../../css/u/uxaxeqbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uy1qryb3w"/><path class="fd6b2rb5y"/><path class="pk3rcgb0u"/><path class="uxaxeqbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:taxi-20-bold" {...props}></Icon>
