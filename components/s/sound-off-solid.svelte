<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b75kccc0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b75kccc0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:sound-off-solid" {...props}></Icon>
