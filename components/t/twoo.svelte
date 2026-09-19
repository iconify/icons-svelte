<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1mh8kczo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1mh8kczo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:twoo" {...props}></Icon>
