<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do0i9ubhw.css';
import '../../css/s/so-0z5bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="do0i9ubhw"/><path class="so-0z5bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sand-battery-48-bold" {...props}></Icon>
