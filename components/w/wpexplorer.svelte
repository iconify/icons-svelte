<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbtk1xkkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dbtk1xkkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:wpexplorer" {...props}></Icon>
