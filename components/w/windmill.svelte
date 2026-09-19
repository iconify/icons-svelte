<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1hw74bbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="f1hw74bbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:windmill" {...props}></Icon>
