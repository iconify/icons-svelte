<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv8u7u5kw.css';
import '../../css/h/h1vzkebnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sv8u7u5kw"/><path class="h1vzkebnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:smartphone-app-widget-stock" {...props}></Icon>
