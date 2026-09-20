<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_smge2np.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u_smge2np"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:x-outline" {...props}></Icon>
