<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5eqbcc6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s5eqbcc6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:to-bottom-one" {...props}></Icon>
