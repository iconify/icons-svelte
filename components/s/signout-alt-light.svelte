<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn3-hqbra.css';
import '../../css/r/r-lddkblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wn3-hqbra"/><path class="r-lddkblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:signout-alt-light" {...props}></Icon>
