<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq_mdu9mg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eq_mdu9mg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:valley" {...props}></Icon>
