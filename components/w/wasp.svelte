<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7ifnpa_v.css';
import '../../css/c/cqaf674jx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="f7ifnpa_v"/><path class="cqaf674jx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:wasp" {...props}></Icon>
