<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2znqy5bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2znqy5bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:tado" {...props}></Icon>
