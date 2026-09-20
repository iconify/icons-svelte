<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn937z2kt.css';
import '../../css/a/afhlj5qgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vn937z2kt"/><path class="afhlj5qgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:treasure-chest-solid" {...props}></Icon>
