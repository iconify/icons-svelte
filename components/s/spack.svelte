<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h27h8qbda.css';
import '../../css/g/giuvwzbiq.css';
import '../../css/c/ckfq98akt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="h27h8qbda"/><path class="giuvwzbiq"/><path class="ckfq98akt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:spack" {...props}></Icon>
