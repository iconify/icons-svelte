<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8hjs2bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h8hjs2bmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:sum" {...props}></Icon>
