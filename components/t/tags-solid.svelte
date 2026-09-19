<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lis884bqb.css';
import '../../css/j/jp1mmybuc.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 lis884bqb"/><path class="clr-i-solid clr-i-solid-path-1 jp1mmybuc"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:tags-solid" {...props}></Icon>
