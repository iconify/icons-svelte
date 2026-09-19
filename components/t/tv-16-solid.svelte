<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkcf_lkax.css';
import '../../css/b/b98f6w00t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jkcf_lkax"/><path clip-rule="evenodd" class="b98f6w00t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:tv-16-solid" {...props}></Icon>
