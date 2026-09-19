<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzijbqbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vzijbqbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:topbuzz" {...props}></Icon>
