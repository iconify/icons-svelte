<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm0hikb7f.css';
import '../../css/f/fc2_4nl4g.css';
import '../../css/v/vczsbmbgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zm0hikb7f"/><path clip-rule="evenodd" class="fc2_4nl4g"/><path class="vczsbmbgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:weblate-wordmark" {...props}></Icon>
