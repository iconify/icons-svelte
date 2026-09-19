<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emdf2hbre.css';
import '../../css/o/o28scob-h.css';
import '../../css/d/dyiul4bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="emdf2hbre"/><path class="o28scob-h"/><path class="dyiul4bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:usdc" {...props}></Icon>
