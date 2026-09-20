<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atcn-d_jw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="atcn-d_jw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:scimitar" {...props}></Icon>
