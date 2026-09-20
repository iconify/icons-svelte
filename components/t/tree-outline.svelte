<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be2tj8b8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="be2tj8b8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tree-outline" {...props}></Icon>
