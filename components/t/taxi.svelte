<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2uby840p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t2uby840p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:taxi" {...props}></Icon>
