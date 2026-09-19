<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_uyzbsvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="o_uyzbsvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:stepforward" {...props}></Icon>
