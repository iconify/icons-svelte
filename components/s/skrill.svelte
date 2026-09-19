<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dais_ibqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="dais_ibqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:skrill" {...props}></Icon>
