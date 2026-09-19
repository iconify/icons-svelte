<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol8lpnb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="ol8lpnb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:vineapp" {...props}></Icon>
