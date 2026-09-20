<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnpxgvtqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mnpxgvtqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wheelchair" {...props}></Icon>
