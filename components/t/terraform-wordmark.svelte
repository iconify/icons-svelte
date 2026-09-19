<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b75v6sxqz.css';
import '../../css/v/v85auebpa.css';
import '../../css/f/f2zzjubol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="b75v6sxqz"/><path class="v85auebpa"/><path class="f2zzjubol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:terraform-wordmark" {...props}></Icon>
