<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9y6adcht.css';
import '../../css/e/e5qdz8_wp.css';
import '../../css/l/l4pq8dbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b9y6adcht"/><path class="e5qdz8_wp"/><path class="l4pq8dbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tandoor-recipes-dark" {...props}></Icon>
